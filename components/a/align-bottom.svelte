<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gx8y2ds-k.css';
import '../../css/i/iktc6lbdf.css';
import '../../css/o/oli4db1ir.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gx8y2ds-k"><path class="iktc6lbdf"/><path class="oli4db1ir"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="akar-icons:align-bottom" {...props}></Icon>
