<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ykl75acdx.css';
import '../../css/u/uvdwn1_nw.css';
import '../../css/b/bg9eedant.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ykl75acdx"/><path class="uvdwn1_nw"/><path class="bg9eedant"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:md-baseball" {...props}></Icon>
