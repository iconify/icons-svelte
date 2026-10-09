<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dw9yj186n.css';
import '../../css/w/waz_2hbmd.css';
import '../../css/n/ne31ywxgx.css';
import '../../css/a/ani345bpd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="dw9yj186n"/><path class="waz_2hbmd"/><path class="ne31ywxgx"/><path class="ani345bpd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:carbon-capture-20" {...props}></Icon>
