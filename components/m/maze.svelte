<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fgu741bmh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fgu741bmh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:maze" {...props}></Icon>
