<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e8458j73b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="e8458j73b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-arrow-dropup-circle" {...props}></Icon>
