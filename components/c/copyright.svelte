<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/m/mvekuabrc.css';
import '../../css/x/xgnuwrb2c.css';
import '../../css/t/tp3qt_bsr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="ft5dv1b6b"><circle class="mvekuabrc"/><path class="xgnuwrb2c"/><path class="tp3qt_bsr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:copyright" {...props}></Icon>
