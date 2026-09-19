<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tj4hj9b4h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="tj4hj9b4h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:arrow-3-trianglepath" {...props}></Icon>
