<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/baq8k5bqx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="baq8k5bqx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:camera-fill-20" {...props}></Icon>
