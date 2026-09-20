<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/x/xs-7jccwj.css';
import '../../css/n/n93rxex0a.css';
import '../../css/u/uy61nnbfh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="xs-7jccwj"/><path class="n93rxex0a"/><path class="uy61nnbfh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand-color:office-stapler-1" {...props}></Icon>
