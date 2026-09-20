<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b808q8dsc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="b808q8dsc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:mend-io-light" {...props}></Icon>
