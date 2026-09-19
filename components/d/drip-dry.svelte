<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uvcnwacac.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":432,"height":512};
const content = `<path class="uvcnwacac"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:drip-dry" {...props}></Icon>
