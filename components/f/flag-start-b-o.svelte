<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zvzfp_pvx.css';
import '../../css/o/oc7q_ob4j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="zvzfp_pvx"/><path class="oc7q_ob4j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gis:flag-start-b-o" {...props}></Icon>
