<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/k/k9v02fbgd.css';
import '../../css/y/yx0j45kpy.css';
import '../../css/f/f-z2sbqxv.css';
import '../../css/a/aq8evbufr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="k9v02fbgd"/><path class="yx0j45kpy"/><circle class="f-z2sbqxv"/><path class="aq8evbufr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:flask-alt-light" {...props}></Icon>
