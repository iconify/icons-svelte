<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9ur0zbdu.css';
import '../../css/v/vlk0aab2e.css';
import '../../css/f/fbiyyn6-d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="s9ur0zbdu"/><path class="vlk0aab2e"/><path class="fbiyyn6-d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:refresh-cw-20-bold" {...props}></Icon>
