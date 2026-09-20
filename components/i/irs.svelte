<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z-_hrufzd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="z-_hrufzd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:irs" {...props}></Icon>
