<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i5_k12b9p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="i5_k12b9p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:raised-curb-under-shoe" {...props}></Icon>
