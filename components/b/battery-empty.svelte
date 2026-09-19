<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t1ao6026r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t1ao6026r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="circum:battery-empty" {...props}></Icon>
