<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bks8__b-f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="bks8__b-f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:micro-center-light" {...props}></Icon>
