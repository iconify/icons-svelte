<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/n/n9_oerbeu.css';
import '../../css/p/po_whzbui.css';
import '../../css/x/xw57btzgo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="n9_oerbeu"/><path class="po_whzbui"/><path class="xw57btzgo"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-flat:gloves" {...props}></Icon>
