<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ii_o2hbdo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ii_o2hbdo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:accent-dark" {...props}></Icon>
