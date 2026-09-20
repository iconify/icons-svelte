<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q22kqbc2u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q22kqbc2u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:mail-star-line" {...props}></Icon>
