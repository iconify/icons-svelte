<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yqjn82ber.css';
import '../../css/z/z0zraxben.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="yqjn82ber"/><path class="z0zraxben"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:edit-48-bold" {...props}></Icon>
