<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tp8_3vedr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="tp8_3vedr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gis:layer-stack-o" {...props}></Icon>
