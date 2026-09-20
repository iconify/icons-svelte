<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/w/wnl9hwkia.css';
import '../../css/u/uf60c4b1b.css';
import '../../css/s/s03jz_ioe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="wnl9hwkia"/><path class="uf60c4b1b"/><path class="s03jz_ioe"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand-color:lift-two-people-elevator" {...props}></Icon>
