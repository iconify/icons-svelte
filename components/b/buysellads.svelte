<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s5kwqkbox.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="s5kwqkbox"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-brands:buysellads" {...props}></Icon>
