<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b0p0fbb2l.css';
import '../../css/t/tsx8_8m-w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="b0p0fbb2l"/><path class="tsx8_8m-w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:parseable" {...props}></Icon>
