<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w67l7eb3p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w67l7eb3p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bx-flag" {...props}></Icon>
