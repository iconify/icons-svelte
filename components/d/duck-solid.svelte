<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ngo_hc0bz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ngo_hc0bz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:duck-solid" {...props}></Icon>
