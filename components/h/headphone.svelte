<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oa0n87zal.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="oa0n87zal"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:headphone" {...props}></Icon>
