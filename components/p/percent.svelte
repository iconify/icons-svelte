<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t63-sob-r.css';
import '../../css/w/wib432g-z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t63-sob-r"/><path class="wib432g-z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="circum:percent" {...props}></Icon>
