<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y7lul5bho.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="y7lul5bho"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:printer-minimalistic-outline" {...props}></Icon>
