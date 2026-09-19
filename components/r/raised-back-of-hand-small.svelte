<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l0lbcs7zx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="l0lbcs7zx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:raised-back-of-hand-small" {...props}></Icon>
