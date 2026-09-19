<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/ho8soe5tw.css';
import '../../css/e/estwjkbcw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ho8soe5tw"/><path class="estwjkbcw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:chineseflag" {...props}></Icon>
