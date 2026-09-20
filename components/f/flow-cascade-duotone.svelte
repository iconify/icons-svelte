<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/u/uithe1bph.css';
import '../../css/a/ar6o_4blw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="uithe1bph"/><path class="ar6o_4blw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:flow-cascade-duotone" {...props}></Icon>
