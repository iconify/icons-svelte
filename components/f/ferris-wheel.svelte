<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xiw61ob7o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xiw61ob7o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:ferris-wheel" {...props}></Icon>
