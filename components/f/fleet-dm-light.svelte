<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tr2b3abya.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="tr2b3abya"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:fleet-dm-light" {...props}></Icon>
