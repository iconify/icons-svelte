<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i19p1mgnu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i19p1mgnu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:flame-broken" {...props}></Icon>
