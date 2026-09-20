<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/w/w9w-myx4m.css';
import '../../css/q/qbji8fb1i.css';
import '../../css/m/mj8ragb7j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="w9w-myx4m"/><path class="qbji8fb1i"/><path class="mj8ragb7j"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand-color:e-commerce-click-buy" {...props}></Icon>
