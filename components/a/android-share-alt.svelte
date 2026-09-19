<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xl0efihro.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xl0efihro"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:android-share-alt" {...props}></Icon>
