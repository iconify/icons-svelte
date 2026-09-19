<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r8kv0lb4e.css';
import '../../css/p/p_echrb7k.css';
import '../../css/i/ilk47r1wz.css';
import '../../css/m/m9jrbcbdh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="r8kv0lb4e"/><path class="p_echrb7k"/><path class="ilk47r1wz"/><path class="m9jrbcbdh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-printer" {...props}></Icon>
