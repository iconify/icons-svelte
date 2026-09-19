<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xiy1i9ggn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1792,"height":1792};
const content = `<path class="xiy1i9ggn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vs:naver-square" {...props}></Icon>
