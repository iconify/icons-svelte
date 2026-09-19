<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b735kbgvp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b735kbgvp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="circum:bacon" {...props}></Icon>
