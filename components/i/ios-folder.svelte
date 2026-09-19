<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lgm3asb6j.css';
import '../../css/p/pvkl0-bwn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="lgm3asb6j"/><path class="pvkl0-bwn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-folder" {...props}></Icon>
