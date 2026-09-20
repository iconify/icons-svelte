<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/l/lvw-4wf-u.css';
import '../../css/e/eqp1polmy.css';
import '../../css/y/ya_ml8bfp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="lvw-4wf-u"/><path class="eqp1polmy"/><path class="ya_ml8bfp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand-color:desktop-action-monitor-remove" {...props}></Icon>
