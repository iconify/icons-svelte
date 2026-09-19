<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gtkgwr-bn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="gtkgwr-bn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:rebol" {...props}></Icon>
