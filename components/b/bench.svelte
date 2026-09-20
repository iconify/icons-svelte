<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qr8xndb1u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="qr8xndb1u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:bench" {...props}></Icon>
