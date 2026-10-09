<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/idk0xib5p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="idk0xib5p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:bird-20" {...props}></Icon>
