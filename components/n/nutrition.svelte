<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zn-i8lbtr.css';
import '../../css/r/r5r-9rbtq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="zn-i8lbtr"/><path class="r5r-9rbtq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="medical-icon:nutrition" {...props}></Icon>
