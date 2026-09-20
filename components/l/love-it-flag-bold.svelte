<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/unprg6b4s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="unprg6b4s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:love-it-flag-bold" {...props}></Icon>
