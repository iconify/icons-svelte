<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zg_qm-3fy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="zg_qm-3fy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:person-standing-dress" {...props}></Icon>
