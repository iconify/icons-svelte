<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ow83bgbqz.css';
import '../../css/p/p0c2m7eex.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ow83bgbqz"/><path class="p0c2m7eex"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:md-information-circle-outline" {...props}></Icon>
