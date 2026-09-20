<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pdm2j-v_h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="pdm2j-v_h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:controller" {...props}></Icon>
