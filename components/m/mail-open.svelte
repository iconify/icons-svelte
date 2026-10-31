<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/j/jezntzhya.css';
import '../../css/p/p-pmhcbxo.css';
import '../../css/t/t6bfzabmi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="jezntzhya wm-k"/><path class="p-pmhcbxo wm-shine"/><path class="t6bfzabmi wm-shine"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-lunar:mail-open" {...props}></Icon>
