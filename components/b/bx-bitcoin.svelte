<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/or-3v0bab.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="or-3v0bab"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bx-bitcoin" {...props}></Icon>
