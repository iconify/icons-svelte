<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qimuysblv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":512};
const content = `<path class="qimuysblv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:file-video" {...props}></Icon>
