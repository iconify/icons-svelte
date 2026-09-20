<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/u/ujb527bml.css';
import '../../css/e/ejz5epb9o.css';
import '../../css/p/p2s_4bb5d.css';
import '../../css/z/zlkv9tksq.css';
import '../../css/y/ybv2_mbnh.css';
import '../../css/u/u6st_da8c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="ujb527bml"/><path class="ejz5epb9o"/><path class="p2s_4bb5d"/><path class="zlkv9tksq"/><path class="ybv2_mbnh"/><path class="u6st_da8c"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand-color:bug-browser-warning" {...props}></Icon>
