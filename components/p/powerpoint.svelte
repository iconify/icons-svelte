<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9cl3zbei.css';
import '../../css/x/xhdah4bbl.css';
import '../../css/v/vw-jy7_8n.css';
import '../../css/r/r6bk7gbmf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="s9cl3zbei"><rect class="xhdah4bbl"/><rect class="vw-jy7_8n"/><path class="r6bk7gbmf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:powerpoint" {...props}></Icon>
