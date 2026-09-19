<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mwhq_1bfc.css';
import '../../css/s/s0kb75b8z.css';
import '../../css/z/zyduq6bqi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="mwhq_1bfc"/><path class="s0kb75b8z"/><path class="zyduq6bqi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-compose-outline" {...props}></Icon>
