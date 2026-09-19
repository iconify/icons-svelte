<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt3-4rb4z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dt3-4rb4z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="circum:grid-4-2" {...props}></Icon>
