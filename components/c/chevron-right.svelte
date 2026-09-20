<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pnap3mb_u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":21,"height":21};
const content = `<path class="pnap3mb_u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="system-uicons:chevron-right" {...props}></Icon>
