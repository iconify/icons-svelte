<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e-phwvw3d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":11,"height":11};
const content = `<path class="e-phwvw3d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:mobile-phone-11" {...props}></Icon>
