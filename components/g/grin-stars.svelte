<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y5f3b3qcl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":496,"height":512};
const content = `<path class="y5f3b3qcl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-regular:grin-stars" {...props}></Icon>
