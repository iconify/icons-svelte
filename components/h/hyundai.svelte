<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dv4vqusdc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dv4vqusdc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:hyundai" {...props}></Icon>
