<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tfmoecckr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tfmoecckr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxl-c-plus-plus" {...props}></Icon>
