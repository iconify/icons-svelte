<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nipz18bkl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="nipz18bkl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:brush-outline" {...props}></Icon>
