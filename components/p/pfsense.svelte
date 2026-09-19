<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tesv8obwz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="tesv8obwz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:pfsense" {...props}></Icon>
