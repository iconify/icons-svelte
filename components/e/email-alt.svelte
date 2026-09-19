<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oavkfobcf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="oavkfobcf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dashicons:email-alt" {...props}></Icon>
