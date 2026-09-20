<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u2e8a6bbt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="u2e8a6bbt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:autocaliweb-light" {...props}></Icon>
