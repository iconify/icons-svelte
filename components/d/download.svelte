<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/th8d8twet.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="th8d8twet"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi-light:download" {...props}></Icon>
