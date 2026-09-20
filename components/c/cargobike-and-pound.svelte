<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z3iq96xor.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="z3iq96xor"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:cargobike-and-pound" {...props}></Icon>
