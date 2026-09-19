<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rtl8plxof.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rtl8plxof"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:butterfly-filled" {...props}></Icon>
