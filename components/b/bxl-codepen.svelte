<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dwb5ovbdg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dwb5ovbdg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxl-codepen" {...props}></Icon>
