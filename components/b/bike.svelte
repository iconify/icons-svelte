<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t743nvnom.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":448};
const content = `<path class="t743nvnom"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:bike" {...props}></Icon>
