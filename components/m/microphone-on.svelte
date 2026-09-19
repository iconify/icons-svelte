<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ndutjfb2y.css';
import '../../css/p/p431tn58m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ndutjfb2y"/><path class="p431tn58m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="circum:microphone-on" {...props}></Icon>
