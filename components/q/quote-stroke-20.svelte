<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n2qr6x11y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="n2qr6x11y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:quote-stroke-20" {...props}></Icon>
