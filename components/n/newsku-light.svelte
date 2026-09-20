<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u671_1o_l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="u671_1o_l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:newsku-light" {...props}></Icon>
