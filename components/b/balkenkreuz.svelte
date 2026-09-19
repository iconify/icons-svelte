<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p0kpkxb9u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="p0kpkxb9u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:balkenkreuz" {...props}></Icon>
