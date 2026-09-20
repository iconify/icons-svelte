<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tkw7e0b0z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":25,"height":25};
const content = `<path class="tkw7e0b0z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:euro" {...props}></Icon>
