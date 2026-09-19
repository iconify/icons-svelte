<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ewxyoiu2q.css';
import '../../css/z/zc4hgcctu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ewxyoiu2q"/><path class="zc4hgcctu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:oldkey" {...props}></Icon>
