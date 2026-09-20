<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rz6ijjbgq.css';
import '../../css/q/qj14hob_f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="rz6ijjbgq"/><path class="qj14hob_f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oui:redeploy" {...props}></Icon>
