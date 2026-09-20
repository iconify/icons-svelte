<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/khq6usb3o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="khq6usb3o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:north-west-circle-line" {...props}></Icon>
