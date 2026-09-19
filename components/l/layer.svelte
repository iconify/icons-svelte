<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lf586bnrj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="lf586bnrj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gis:layer" {...props}></Icon>
