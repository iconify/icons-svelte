<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ct5lbkz2a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ct5lbkz2a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:google-lens" {...props}></Icon>
