<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/khgv06bhg.css';
import '../../css/e/eb9nnbb2q.css';
import '../../css/m/m2o3sh-9c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":36,"height":36};
const content = `<path class="clr-i-outline clr-i-outline-path-1 khgv06bhg"/><path class="clr-i-outline clr-i-outline-path-2 eb9nnbb2q"/><path class="m2o3sh-9c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="clarity:block-quote-line" {...props}></Icon>
