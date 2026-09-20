<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/z/zkbga2bms.css';
import '../../css/i/i2qezbnqp.css';
import '../../css/q/q8wbu63xu.css';
import '../../css/d/dvxkj65od.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":21,"height":21};
const content = `<g transform="translate(2 2)" class="bi12bsetm"><g class="zkbga2bms"><circle class="i2qezbnqp"/><path class="q8wbu63xu"/></g><circle class="dvxkj65od"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="system-uicons:info-circle" {...props}></Icon>
