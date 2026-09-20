<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/m/mgljn7bfo.css';
import '../../css/z/znusfdc4c.css';
import '../../css/x/xsb0bgv9z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="mgljn7bfo"/><path class="znusfdc4c"/><path class="xsb0bgv9z"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:restart-broken" {...props}></Icon>
