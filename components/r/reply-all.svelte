<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sj8vhkajy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sj8vhkajy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:reply-all" {...props}></Icon>
