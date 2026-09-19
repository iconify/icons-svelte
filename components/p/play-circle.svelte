<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wqbkv8u2i.css';
import '../../css/r/ro3rk-b0o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wqbkv8u2i"/><path class="ro3rk-b0o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:play-circle" {...props}></Icon>
