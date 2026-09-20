<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gzhztek1e.css';
import '../../css/a/a1lsv6bmw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="gzhztek1e"/><path class="a1lsv6bmw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:actual-budget" {...props}></Icon>
