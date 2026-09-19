<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ea9jj1p6e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ea9jj1p6e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-arrow-left" {...props}></Icon>
