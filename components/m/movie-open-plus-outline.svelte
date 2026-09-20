<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a_bwmobsb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a_bwmobsb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:movie-open-plus-outline" {...props}></Icon>
