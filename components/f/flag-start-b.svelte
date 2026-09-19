<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ywx41bb_f.css';
import '../../css/o/oc7q_ob4j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="ywx41bb_f"/><path class="oc7q_ob4j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gis:flag-start-b" {...props}></Icon>
