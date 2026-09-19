<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ilyi3y8_e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="ilyi3y8_e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:magento" {...props}></Icon>
