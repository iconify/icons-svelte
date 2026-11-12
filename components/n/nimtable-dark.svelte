<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wdyn042hz.css';
import '../../css/l/ldgegdkhl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="wdyn042hz"/><path class="ldgegdkhl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:nimtable-dark" {...props}></Icon>
