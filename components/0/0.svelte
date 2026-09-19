<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nfs5vejnu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="nfs5vejnu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:0" {...props}></Icon>
