<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yg-xa_blz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":26,"height":26};
const content = `<path class="yg-xa_blz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wpf:retro-tv" {...props}></Icon>
