<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oy01k2xql.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oy01k2xql"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:link-x" {...props}></Icon>
