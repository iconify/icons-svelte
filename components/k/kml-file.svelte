<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y43w1h50n.css';
import '../../css/j/jqc7hmb-f.css';
import '../../css/x/x2bi_jl-x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="y43w1h50n"/><path class="jqc7hmb-f"/><path class="x2bi_jl-x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gis:kml-file" {...props}></Icon>
