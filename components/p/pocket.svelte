<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mi5he_bmo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":432,"height":384};
const content = `<path class="mi5he_bmo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:pocket" {...props}></Icon>
