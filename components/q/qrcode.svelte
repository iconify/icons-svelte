<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sh_6zjivc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sh_6zjivc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-outline:qrcode" {...props}></Icon>
