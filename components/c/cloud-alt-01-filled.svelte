<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nfbuhbbdr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nfbuhbbdr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:cloud-alt-01-filled" {...props}></Icon>
