<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ydla-ob9l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ydla-ob9l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:blueprint-helmet-1-bold" {...props}></Icon>
