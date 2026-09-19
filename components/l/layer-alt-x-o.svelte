<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ymjpdm2-p.css';
import '../../css/h/ha1q3jlnu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="ymjpdm2-p"/><path class="ha1q3jlnu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gis:layer-alt-x-o" {...props}></Icon>
