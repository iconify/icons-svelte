<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/t/t9m1ntheo.css';
import '../../css/y/yl4kardsp.css';
import '../../css/o/op8v83bse.css';
import '../../css/d/dsgjiybzm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="t9m1ntheo"/><path class="wm-a yl4kardsp"/><path class="op8v83bse wm-a"/><path class="dsgjiybzm wm-s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:bomb" {...props}></Icon>
