<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sv7ay2bxn.css';
import '../../css/a/a85tzjcpz.css';
import '../../css/b/b319z3bxe.css';
import '../../css/q/q1l6tebrz.css';
import '../../css/x/xp-ry7bst.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="sv7ay2bxn"><path class="a85tzjcpz wm-shadow"/><path class="b319z3bxe wm-shadow"/><path class="q1l6tebrz"/><path class="xp-ry7bst"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-brutal:air-vent" {...props}></Icon>
