<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/i/ijqz56wxk.css';
import '../../css/g/gw9e2jbsa.css';
import '../../css/f/foeim5b7u.css';
import '../../css/j/jrsma9byt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="ijqz56wxk"/><path class="gw9e2jbsa"/><path clip-rule="evenodd" class="foeim5b7u"/><path class="jrsma9byt"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:bell-add-outline" {...props}></Icon>
