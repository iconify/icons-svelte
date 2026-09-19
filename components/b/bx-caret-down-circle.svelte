<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p7ufp8b5m.css';
import '../../css/w/wqbkv8u2i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p7ufp8b5m"/><path class="wqbkv8u2i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bx-caret-down-circle" {...props}></Icon>
