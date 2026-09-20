<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qt-2uw01i.css';
import '../../css/c/clcbemb9z.css';
import '../../css/z/zqkur5bsc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="qt-2uw01i"/><path class="clcbemb9z"/><path class="zqkur5bsc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:mkvpriority" {...props}></Icon>
