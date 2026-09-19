<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/szdg7sb9v.css';
import '../../css/i/inw9uqdux.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="szdg7sb9v"/><path class="inw9uqdux"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gis:layer-alt-poi" {...props}></Icon>
