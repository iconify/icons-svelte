<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m1uph2bhc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="m1uph2bhc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:elementaryos" {...props}></Icon>
