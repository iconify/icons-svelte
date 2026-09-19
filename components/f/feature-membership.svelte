<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qr1e2hb_o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="qr1e2hb_o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:feature-membership" {...props}></Icon>
