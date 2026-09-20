<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/osuby9bie.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="osuby9bie"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:hamburger-menu-back" {...props}></Icon>
