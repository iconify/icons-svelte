<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pg28z8byr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pg28z8byr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bx-menu-alt-left" {...props}></Icon>
