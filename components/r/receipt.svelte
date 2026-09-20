<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/okv6f5bis.css';
import '../../css/u/uq6a4ac5u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="okv6f5bis"/><path class="uq6a4ac5u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:receipt" {...props}></Icon>
