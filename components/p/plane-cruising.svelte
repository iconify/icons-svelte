<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oapu8s0xw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="oapu8s0xw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:plane-cruising" {...props}></Icon>
