<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gwc1l2bfp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="gwc1l2bfp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:plain-week-dark" {...props}></Icon>
