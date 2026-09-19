<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zq453ybdp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="zq453ybdp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:rectangle-stack-person-crop" {...props}></Icon>
