<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xas62ub0g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xas62ub0g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="circum:file-on" {...props}></Icon>
