<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wc_rtl98b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wc_rtl98b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:rewind" {...props}></Icon>
