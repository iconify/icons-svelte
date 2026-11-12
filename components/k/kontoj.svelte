<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/agda5ibxs.css';
import '../../css/n/nfv5mkb1f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="agda5ibxs"/><path class="nfv5mkb1f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:kontoj" {...props}></Icon>
