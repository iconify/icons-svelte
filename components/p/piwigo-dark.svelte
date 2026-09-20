<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/ht9sztzrk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ht9sztzrk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:piwigo-dark" {...props}></Icon>
