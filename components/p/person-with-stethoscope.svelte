<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ra0v5m8_f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="ra0v5m8_f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:person-with-stethoscope" {...props}></Icon>
