<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vyofm5_zg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vyofm5_zg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="circum:pause-1" {...props}></Icon>
