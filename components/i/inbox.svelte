<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/clltq9axj.css';
import '../../css/d/dlpepfyti.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="clltq9axj"/><path class="dlpepfyti"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:inbox" {...props}></Icon>
