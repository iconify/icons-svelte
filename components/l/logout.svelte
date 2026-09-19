<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rahk9_b2d.css';
import '../../css/x/xjog0ebft.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rahk9_b2d"/><path class="xjog0ebft"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="circum:logout" {...props}></Icon>
