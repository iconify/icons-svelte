<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zqvz_ub4o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":21,"height":21};
const content = `<path class="zqvz_ub4o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="system-uicons:laptop" {...props}></Icon>
