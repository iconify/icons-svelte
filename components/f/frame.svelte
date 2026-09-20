<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nxown8zph.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="nxown8zph"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-line-icons:frame" {...props}></Icon>
