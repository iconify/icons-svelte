<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/ww38k_b5y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ww38k_b5y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:hacker-news" {...props}></Icon>
