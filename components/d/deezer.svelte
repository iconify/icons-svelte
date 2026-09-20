<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/okvyj4bjj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="okvyj4bjj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:deezer" {...props}></Icon>
