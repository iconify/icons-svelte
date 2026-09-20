<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bvs13wbop.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="bvs13wbop"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:datadog-light" {...props}></Icon>
