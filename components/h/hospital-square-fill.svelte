<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j_ei-vbiq.css';
import '../../css/v/vexocobrh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j_ei-vbiq"/><path class="vexocobrh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:hospital-square-fill" {...props}></Icon>
