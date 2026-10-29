<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f__zufvhz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f__zufvhz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:letter-u" {...props}></Icon>
