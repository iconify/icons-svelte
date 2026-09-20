<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p152e5bda.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p152e5bda"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:archlinux" {...props}></Icon>
