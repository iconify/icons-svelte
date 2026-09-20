<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o6r3qlnuf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="o6r3qlnuf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:car-and-wrench" {...props}></Icon>
