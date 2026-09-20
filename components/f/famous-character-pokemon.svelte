<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/d/d5nequhdi.css';
import '../../css/u/ujk-8v4-a.css';
import '../../css/u/u0ivgpm6f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="d5nequhdi"/><path class="ujk-8v4-a"/><path class="u0ivgpm6f"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand-color:famous-character-pokemon" {...props}></Icon>
