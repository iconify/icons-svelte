<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k0c4xobxi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="k0c4xobxi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gis:earth-asia-o" {...props}></Icon>
