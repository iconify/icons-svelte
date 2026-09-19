<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/w/wal7ho3rf.css';
import '../../css/v/v6hl1hb8w.css';
import '../../css/o/otljbkb5n.css';
import '../../css/x/xtyxypbue.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="wal7ho3rf"/><path class="v6hl1hb8w"/><path class="otljbkb5n"/><path class="xtyxypbue"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:arrange" {...props}></Icon>
