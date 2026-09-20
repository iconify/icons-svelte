<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/o/od8l_7bsn.css';
import '../../css/s/sck_s-bkk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<g class="cuyn6tgcc"><path class="od8l_7bsn"/><path class="ouiIcon__fillSecondary sck_s-bkk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oui:app-add-data" {...props}></Icon>
