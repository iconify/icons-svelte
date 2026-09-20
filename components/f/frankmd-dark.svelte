<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/snaubdbur.css';
import '../../css/z/zh_kfpbbn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="snaubdbur"/><path class="zh_kfpbbn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:frankmd-dark" {...props}></Icon>
