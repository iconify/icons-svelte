<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i_xehnt6f.css';
import '../../css/z/zrbhk7b_w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="i_xehnt6f"/><path class="zrbhk7b_w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:h2-molecule-20" {...props}></Icon>
