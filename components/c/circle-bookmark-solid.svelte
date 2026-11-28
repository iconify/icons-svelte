<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/div889bba.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="div889bba"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:circle-bookmark-solid" {...props}></Icon>
