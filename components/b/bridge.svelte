<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zoa2debvg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zoa2debvg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:bridge" {...props}></Icon>
