<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zhfnc2dzw.css';
import '../../css/c/ccz24ggpe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="zhfnc2dzw"/><path class="ccz24ggpe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:myheats-dark" {...props}></Icon>
