<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hk5s5sbxi.css';
import '../../css/e/ecj_qnblt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="hk5s5sbxi"/><path class="ecj_qnblt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:copilot-light" {...props}></Icon>
