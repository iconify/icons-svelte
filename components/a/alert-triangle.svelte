<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mfqbxj_2g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":472,"height":408};
const content = `<path class="mfqbxj_2g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:alert-triangle" {...props}></Icon>
