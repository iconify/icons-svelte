<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w9u-62fmy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w9u-62fmy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="circum:home" {...props}></Icon>
