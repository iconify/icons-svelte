<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/s/sx0o_fbse.css';
import '../../css/h/h078bhb2y.css';
import '../../css/n/ny070ob4l.css';
import '../../css/f/fha9r6xzf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="sx0o_fbse"/><path class="h078bhb2y"/><path class="ny070ob4l"/><path class="fha9r6xzf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:chart-radar-duotone" {...props}></Icon>
