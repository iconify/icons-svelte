<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xn5eo9bqs.css';
import '../../css/x/xutqjtbzv.css';
import '../../css/n/ngkwocppj.css';
import '../../css/g/gll9pmo4p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="xn5eo9bqs"><path class="xutqjtbzv"/><path class="ngkwocppj"/><path class="gll9pmo4p"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="matita:layers" {...props}></Icon>
