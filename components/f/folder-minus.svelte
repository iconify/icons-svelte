<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/a/a9xk7ubfw.css';
import '../../css/l/lu4ljlbqq.css';
import '../../css/k/kyur8bcfd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="a9xk7ubfw"/><path class="lu4ljlbqq"/><path class="kyur8bcfd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:folder-minus" {...props}></Icon>
