<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/usb7uf1xx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="usb7uf1xx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:balloon" {...props}></Icon>
