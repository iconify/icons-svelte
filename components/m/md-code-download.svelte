<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g8-n1ibyr.css';
import '../../css/z/zfla53asp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="g8-n1ibyr"/><path class="zfla53asp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:md-code-download" {...props}></Icon>
