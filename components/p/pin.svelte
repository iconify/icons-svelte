<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zdq8rzv_p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zdq8rzv_p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:pin" {...props}></Icon>
