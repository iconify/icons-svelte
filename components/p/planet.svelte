<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ogi60eb_u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ogi60eb_u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nimbus:planet" {...props}></Icon>
