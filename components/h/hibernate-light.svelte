<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/q/qypeg9b1z.css';
import '../../css/s/sloideb6m.css';
import '../../css/t/tlw2j3bce.css';
import '../../css/d/d9990mo1a.css';
import '../../css/c/cc3hlpb5m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<g class="ft5dv1b6b"><rect class="qypeg9b1z"/><path class="sloideb6m"/><path class="tlw2j3bce"/><path class="d9990mo1a"/><path class="cc3hlpb5m"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="skill-icons:hibernate-light" {...props}></Icon>
