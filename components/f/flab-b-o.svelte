<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oc7q_ob4j.css';
import '../../css/o/o7vd0ghvf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="oc7q_ob4j"/><path class="o7vd0ghvf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gis:flab-b-o" {...props}></Icon>
