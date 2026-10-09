<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qox-itb7z.css';
import '../../css/i/ijj0fga_g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="qox-itb7z"/><path class="ijj0fga_g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:contact-20-bold" {...props}></Icon>
