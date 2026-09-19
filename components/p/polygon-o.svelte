<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lagifclqn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="lagifclqn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gis:polygon-o" {...props}></Icon>
