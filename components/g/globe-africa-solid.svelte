<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bve_hvb-f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="bve_hvb-f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:globe-africa-solid" {...props}></Icon>
