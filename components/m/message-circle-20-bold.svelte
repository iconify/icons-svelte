<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kq5np1vsf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="kq5np1vsf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:message-circle-20-bold" {...props}></Icon>
