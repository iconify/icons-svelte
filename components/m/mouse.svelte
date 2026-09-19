<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vllpgtbvv.css';
import '../../css/y/yd1k4mbzu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="vllpgtbvv"/><path class="yd1k4mbzu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ep:mouse" {...props}></Icon>
