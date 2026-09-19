<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xs2w-lbzi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="xs2w-lbzi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gis:layer-up" {...props}></Icon>
