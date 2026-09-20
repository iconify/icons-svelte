<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a2bqtbcvs.css';
import '../../css/u/uq8jn4bmu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="a2bqtbcvs"/><path class="uq8jn4bmu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:android-police" {...props}></Icon>
