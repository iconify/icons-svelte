<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w46o3ib0w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="w46o3ib0w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:md-return-right" {...props}></Icon>
