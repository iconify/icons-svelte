<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9nmekbvz.css';
import '../../css/i/i4it1pzvk.css';
import '../../css/t/t218te2ox.css';
import '../../css/e/ezx00wbry.css';
import '../../css/y/ytq6kubqz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="i4it1pzvk wm-deco"/><path class="t218te2ox wm-deco"/><path class="ezx00wbry wm-k"/><path class="wm-a ytq6kubqz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:address-book-blueprint" {...props}></Icon>
