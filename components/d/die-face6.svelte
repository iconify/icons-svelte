<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qr2w7xw8k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="qr2w7xw8k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:die-face6" {...props}></Icon>
