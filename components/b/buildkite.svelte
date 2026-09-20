<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eq4svq8ys.css';
import '../../css/r/rbmgisbte.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="eq4svq8ys"/><path class="rbmgisbte"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:buildkite" {...props}></Icon>
