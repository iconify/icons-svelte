<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zoldi4b3u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="zoldi4b3u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-color:arrow-transfer-diagonal-2-flat" {...props}></Icon>
