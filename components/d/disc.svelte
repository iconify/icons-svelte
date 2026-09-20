<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mjiuvabtk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="mjiuvabtk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-line-icons:disc" {...props}></Icon>
