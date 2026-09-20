<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jy26aup1d.css';
import '../../css/w/w5x0zccyo.css';
import '../../css/k/kv7e38bui.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jy26aup1d"/><path class="w5x0zccyo"/><path class="kv7e38bui"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:headphones-1-bold" {...props}></Icon>
