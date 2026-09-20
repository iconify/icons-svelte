<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x3kws5b8f.css';
import '../../css/r/rqm0q0u6i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x3kws5b8f"/><path class="rqm0q0u6i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:dam-7-filled" {...props}></Icon>
