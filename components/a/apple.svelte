<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tkyxqo7ox.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tkyxqo7ox"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="circum:apple" {...props}></Icon>
