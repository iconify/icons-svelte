<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/arp62jbme.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="arp62jbme"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nimbus:chevron-up" {...props}></Icon>
