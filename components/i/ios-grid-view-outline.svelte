<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e6rd46bfh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="e6rd46bfh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-grid-view-outline" {...props}></Icon>
