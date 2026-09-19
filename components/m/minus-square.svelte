<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lu7ms5bok.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":384};
const content = `<path class="lu7ms5bok"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:minus-square" {...props}></Icon>
