<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t769otr5u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="t769otr5u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:people-sleeping-in-bunkbeds-in-eaved-open-gabled-building" {...props}></Icon>
