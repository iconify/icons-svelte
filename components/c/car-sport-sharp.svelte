<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hrcok4b2c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="hrcok4b2c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:car-sport-sharp" {...props}></Icon>
