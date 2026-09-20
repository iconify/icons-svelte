<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/twfeyencb.css';
import '../../css/h/hnsdbi_4t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="twfeyencb"/><path class="hnsdbi_4t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:rancher-fleet" {...props}></Icon>
