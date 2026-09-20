<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/q/qul6b_1xq.css';
import '../../css/k/kdanzpkky.css';
import '../../css/n/n60idm96g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="qul6b_1xq"/><path class="kdanzpkky"/><path class="n60idm96g"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand-color:presentation-audience" {...props}></Icon>
