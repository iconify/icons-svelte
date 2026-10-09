<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pt0-ruido.css';
import '../../css/b/b8usfzbqp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="pt0-ruido"/><path class="b8usfzbqp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:camera-20-bold" {...props}></Icon>
