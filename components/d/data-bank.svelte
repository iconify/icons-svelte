<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/h/h6t39xbyu.css';
import '../../css/n/n-y7t6i4r.css';
import '../../css/j/jzj1j7b_h.css';
import '../../css/q/qwgjhnbgj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="h6t39xbyu"/><path class="n-y7t6i4r"/><rect class="jzj1j7b_h"/><rect class="qwgjhnbgj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:data-bank" {...props}></Icon>
