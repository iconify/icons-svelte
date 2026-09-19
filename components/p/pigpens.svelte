<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ntrv586rn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1025,"height":1024};
const content = `<path class="ntrv586rn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:pigpens" {...props}></Icon>
