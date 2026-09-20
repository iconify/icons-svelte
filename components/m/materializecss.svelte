<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zi4wg5b2c.css';
import '../../css/o/obi015b0i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="zi4wg5b2c"/><path class="obi015b0i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:materializecss" {...props}></Icon>
