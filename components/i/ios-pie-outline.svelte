<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bn_mz6b4i.css';
import '../../css/r/rf5rhacdh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="bn_mz6b4i"/><path class="rf5rhacdh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-pie-outline" {...props}></Icon>
