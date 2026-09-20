<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ebjj2yi8t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ebjj2yi8t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:etesync-dark" {...props}></Icon>
