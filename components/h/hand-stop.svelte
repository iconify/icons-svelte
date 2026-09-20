<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gtpr4ibiq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="gtpr4ibiq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zondicons:hand-stop" {...props}></Icon>
