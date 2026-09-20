<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/l/lq5xb8bez.css';
import '../../css/o/o_78qwqmp.css';
import '../../css/h/hxiimb9fh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="lq5xb8bez"/><path class="o_78qwqmp"/><path class="hxiimb9fh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="majesticons:folder-plus" {...props}></Icon>
