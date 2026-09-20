<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wl0ks-bnl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wl0ks-bnl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:file-contract" {...props}></Icon>
