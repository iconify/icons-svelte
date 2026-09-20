<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ysdzf_bla.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ysdzf_bla"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:microsoft-windows" {...props}></Icon>
