<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o3n-n5b1t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="o3n-n5b1t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:omnom" {...props}></Icon>
