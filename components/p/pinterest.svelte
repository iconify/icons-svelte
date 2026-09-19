<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/es10opblc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":18,"height":24};
const content = `<path class="es10opblc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:pinterest" {...props}></Icon>
