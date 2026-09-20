<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k210_ne1k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k210_ne1k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:linuxserver" {...props}></Icon>
