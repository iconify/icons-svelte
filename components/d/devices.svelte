<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ecbob4veg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ecbob4veg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:devices" {...props}></Icon>
