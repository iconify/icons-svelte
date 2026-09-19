<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hrl_9-k9t.css';
import '../../css/j/ja9psewjq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="hrl_9-k9t"/><path class="ja9psewjq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:file-tray-full" {...props}></Icon>
