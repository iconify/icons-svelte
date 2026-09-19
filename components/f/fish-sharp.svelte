<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fe4b7xbxm.css';
import '../../css/n/ncwehzbfp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="fe4b7xbxm"/><path class="ncwehzbfp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:fish-sharp" {...props}></Icon>
