<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z5oua77in.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z5oua77in"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:framer-logo" {...props}></Icon>
