<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iuisidc2h.css';
import '../../css/k/kensec86u.css';
import '../../css/t/tuvs7pa-d.css';
import '../../css/j/j-0-v4b_h.css';
import '../../css/x/xfkcrqbqu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="iuisidc2h"/><path class="kensec86u"/><path class="tuvs7pa-d"/><path class="j-0-v4b_h"/><path class="xfkcrqbqu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:pve-ups" {...props}></Icon>
