<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/piz_jmb7s.css';
import '../../css/z/zs8x37yqc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="piz_jmb7s"/><path class="zs8x37yqc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:chat-add-16" {...props}></Icon>
