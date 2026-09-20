<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xmz2-lxle.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xmz2-lxle"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:pin-alt-1-line" {...props}></Icon>
