<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tz4xy4xop.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="tz4xy4xop"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:bag" {...props}></Icon>
