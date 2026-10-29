<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t2_fu_bwp.css';
import '../../css/r/r42-uz-ln.css';
import '../../css/f/fnyksabiy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t2_fu_bwp"/><path class="r42-uz-ln"/><path class="fnyksabiy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-bauhaus:copy" {...props}></Icon>
