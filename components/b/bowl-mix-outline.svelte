<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c0_ig5bcg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c0_ig5bcg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:bowl-mix-outline" {...props}></Icon>
