<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/j/j80x_6w1a.css';
import '../../css/r/r3uw8bcwl.css';
import '../../css/i/ixd243bqj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="j80x_6w1a"/><path class="r3uw8bcwl"/><path class="ixd243bqj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand-color:responsive-design-expand" {...props}></Icon>
