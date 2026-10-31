<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/g/gcn8wsjcn.css';
import '../../css/r/rkats6bfp.css';
import '../../css/i/ieyfkloei.css';
import '../../css/o/ocyyo8bxi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":300,"height":200};
const content = `<g class="bi12bsetm"><path class="gcn8wsjcn"/><path class="rkats6bfp"/><path class="ieyfkloei"/><path class="ocyyo8bxi"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cif:ls" {...props}></Icon>
