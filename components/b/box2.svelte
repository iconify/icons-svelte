<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qr9ai5wvc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="qr9ai5wvc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:box2" {...props}></Icon>
