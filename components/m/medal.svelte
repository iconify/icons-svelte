<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xfs19bcvf.css';
import '../../css/a/an4c_3b3j.css';
import '../../css/y/yjo7ewdyq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<circle class="xfs19bcvf"/><path class="an4c_3b3j"/><path class="yjo7ewdyq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:medal" {...props}></Icon>
