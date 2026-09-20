<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l03st-bdy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="l03st-bdy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:calculator-solid" {...props}></Icon>
