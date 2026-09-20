<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/htn-dr4sx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="htn-dr4sx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:email" {...props}></Icon>
