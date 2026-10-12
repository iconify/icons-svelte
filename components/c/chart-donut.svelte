<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/m/m95cihbre.css';
import '../../css/m/mpf1g8bav.css';
import '../../css/m/mixyu8bak.css';
import '../../css/b/b1fjtovtf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="m95cihbre"/><circle class="mpf1g8bav"/><circle class="mixyu8bak"/><path class="b1fjtovtf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="andrsrxn:chart-donut" {...props}></Icon>
