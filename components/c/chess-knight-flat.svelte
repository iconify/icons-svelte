<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/f/fhn12jz8i.css';
import '../../css/d/dlkgg4zpw.css';
import '../../css/c/c29b-_v0n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="fhn12jz8i"/><path class="dlkgg4zpw"/><path clip-rule="evenodd" class="c29b-_v0n"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp-color:chess-knight-flat" {...props}></Icon>
