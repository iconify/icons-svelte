<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bcoil0bua.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bcoil0bua"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:magic-wand" {...props}></Icon>
