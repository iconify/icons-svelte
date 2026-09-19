<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/es8u0ebhl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="es8u0ebhl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="humbleicons:mobile" {...props}></Icon>
