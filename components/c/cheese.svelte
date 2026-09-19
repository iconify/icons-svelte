<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/c/c-o5zcb4l.css';
import '../../css/h/hpe3joppp.css';
import '../../css/g/gtci1mb3a.css';
import '../../css/b/b1y56jbxn.css';
import '../../css/d/drjfn8ypm.css';
import '../../css/w/wbccjbclf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="ft5dv1b6b"><path class="c-o5zcb4l"/><path class="hpe3joppp"/><circle class="gtci1mb3a"/><circle class="b1y56jbxn"/><circle class="drjfn8ypm"/><circle class="wbccjbclf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:cheese" {...props}></Icon>
