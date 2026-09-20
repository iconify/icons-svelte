<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q8gqn_bfy.css';
import '../../css/u/uxjr5m63m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="q8gqn_bfy"/><path class="uxjr5m63m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:folder-controller-open" {...props}></Icon>
