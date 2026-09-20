<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oyop8zbfw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="oyop8zbfw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:hanko" {...props}></Icon>
