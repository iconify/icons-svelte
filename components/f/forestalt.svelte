<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q192h5cgl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":768,"height":1024};
const content = `<path class="q192h5cgl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:forestalt" {...props}></Icon>
