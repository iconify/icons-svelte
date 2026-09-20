<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ke1i97i9e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ke1i97i9e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:mail-star-fill" {...props}></Icon>
