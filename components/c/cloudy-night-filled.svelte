<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/luqxxebuz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="luqxxebuz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:cloudy-night-filled" {...props}></Icon>
