<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/c/c4if0pwhb.css';
import '../../css/j/jtth9xbar.css';
import '../../css/c/cxmb-_6za.css';
import '../../css/t/t6wz8cb3t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="c4if0pwhb"/><path class="jtth9xbar"/><path class="cxmb-_6za"/><circle class="t6wz8cb3t"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="proicons:reactjs" {...props}></Icon>
