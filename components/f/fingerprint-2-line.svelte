<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zecxc7b2n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zecxc7b2n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:fingerprint-2-line" {...props}></Icon>
