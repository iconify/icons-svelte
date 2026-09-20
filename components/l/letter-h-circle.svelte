<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fbuslpbfy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fbuslpbfy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:letter-h-circle" {...props}></Icon>
