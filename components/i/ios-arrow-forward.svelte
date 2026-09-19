<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e0h0i5bdv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="e0h0i5bdv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-arrow-forward" {...props}></Icon>
