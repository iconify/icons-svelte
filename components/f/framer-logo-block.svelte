<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fwy41vlmz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="fwy41vlmz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:framer-logo-block" {...props}></Icon>
