<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k8i5lmblk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="k8i5lmblk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:person-jumping-on-bouncy-cushion" {...props}></Icon>
