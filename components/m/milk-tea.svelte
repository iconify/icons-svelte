<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wt4gf1vpk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="wt4gf1vpk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ep:milk-tea" {...props}></Icon>
