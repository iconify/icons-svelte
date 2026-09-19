<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s_6rmtujx.css';
import '../../css/x/xmy0diffs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="s_6rmtujx"/><path class="xmy0diffs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ipod" {...props}></Icon>
