<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d4az-pqpf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="d4az-pqpf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gis:rectangle-o" {...props}></Icon>
