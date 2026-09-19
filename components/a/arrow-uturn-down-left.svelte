<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e_qr2kb6i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="e_qr2kb6i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:arrow-uturn-down-left" {...props}></Icon>
