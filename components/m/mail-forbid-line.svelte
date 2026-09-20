<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/avh0x4bfp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="avh0x4bfp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:mail-forbid-line" {...props}></Icon>
