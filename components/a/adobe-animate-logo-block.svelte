<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sh-974bjo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="sh-974bjo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:adobe-animate-logo-block" {...props}></Icon>
