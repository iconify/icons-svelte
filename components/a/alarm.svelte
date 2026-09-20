<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/n/n1x38_bty.css';
import '../../css/l/l8zqkabzp.css';
import '../../css/s/su8twpfed.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="n1x38_bty"/><path class="l8zqkabzp"/><path class="su8twpfed"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:alarm" {...props}></Icon>
