<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wg5_eab7x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="wg5_eab7x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:open-source-initiative-light" {...props}></Icon>
