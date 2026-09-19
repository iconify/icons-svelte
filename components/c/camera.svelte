<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cv0mj9bsl.css';
import '../../css/x/xbmduob_b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<circle class="cv0mj9bsl"/><path class="xbmduob_b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:camera" {...props}></Icon>
