<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o4ca86bnz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="o4ca86bnz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:cloudy" {...props}></Icon>
