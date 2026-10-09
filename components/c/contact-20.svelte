<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bx89adb5k.css';
import '../../css/p/p-13vkqjz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="bx89adb5k"/><path class="p-13vkqjz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:contact-20" {...props}></Icon>
