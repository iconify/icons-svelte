<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/es93enghp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="es93enghp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:double-caret-right-small-solid" {...props}></Icon>
