<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/m/mszq7jb9m.css';
import '../../css/s/scn0e15ut.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="mszq7jb9m"/><path clip-rule="evenodd" class="scn0e15ut"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp-color:eject-square-flat" {...props}></Icon>
