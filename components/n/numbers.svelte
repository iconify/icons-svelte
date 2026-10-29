<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xdpj7wl7x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xdpj7wl7x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:numbers" {...props}></Icon>
