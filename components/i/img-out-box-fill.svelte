<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/v/vib04l-vj.css';
import '../../css/i/i0vrgebuc.css';
import '../../css/e/e7ble4bav.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="vib04l-vj"/><path class="i0vrgebuc"/><path class="e7ble4bav"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:img-out-box-fill" {...props}></Icon>
