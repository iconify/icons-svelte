<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fon56od1l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="fon56od1l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dashicons:camera-alt" {...props}></Icon>
