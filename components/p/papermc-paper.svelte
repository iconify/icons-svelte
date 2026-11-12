<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n73j_hptb.css';
import '../../css/g/gl-4o7slp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="n73j_hptb"/><path class="gl-4o7slp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:papermc-paper" {...props}></Icon>
