<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n68d9jb5y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n68d9jb5y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:puzzle-check-outline" {...props}></Icon>
