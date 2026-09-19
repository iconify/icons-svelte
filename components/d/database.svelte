<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vlf5z0fpf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vlf5z0fpf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="circum:database" {...props}></Icon>
