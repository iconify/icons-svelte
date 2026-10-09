<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i24lvpsxg.css';
import '../../css/k/kv_lf4f7r.css';
import '../../css/x/xmfmqwpbn.css';
import '../../css/i/iwgm76bjf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="i24lvpsxg"/><path class="kv_lf4f7r"/><path class="xmfmqwpbn"/><path class="iwgm76bjf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:mic-off-20-bold" {...props}></Icon>
