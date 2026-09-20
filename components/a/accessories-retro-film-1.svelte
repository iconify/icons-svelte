<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/k/k13g4ld-j.css';
import '../../css/j/jpx3_871k.css';
import '../../css/b/b_yth_bng.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="k13g4ld-j"/><path class="jpx3_871k"/><path class="b_yth_bng"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand-color:accessories-retro-film-1" {...props}></Icon>
