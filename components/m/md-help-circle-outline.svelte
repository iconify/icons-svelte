<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ow83bgbqz.css';
import '../../css/o/oexci5_ie.css';
import '../../css/w/wahgcobfj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ow83bgbqz"/><path class="oexci5_ie"/><path class="wahgcobfj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:md-help-circle-outline" {...props}></Icon>
