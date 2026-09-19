<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zi0g28_vu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="zi0g28_vu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:long-arrow-alt-left" {...props}></Icon>
