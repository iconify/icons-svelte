<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bmksxpbjb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="bmksxpbjb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:crusher-20" {...props}></Icon>
