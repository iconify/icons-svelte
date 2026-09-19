<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r1huxznhc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r1huxznhc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="circum:paperplane" {...props}></Icon>
