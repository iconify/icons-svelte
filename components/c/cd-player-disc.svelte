<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/p/pw8owgtbs.css';
import '../../css/t/tvp1jib9y.css';
import '../../css/r/roucdszvd.css';
import '../../css/s/sgw5l6b8j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="pw8owgtbs"/><path class="tvp1jib9y"/><path class="roucdszvd"/><path class="sgw5l6b8j"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand-color:cd-player-disc" {...props}></Icon>
