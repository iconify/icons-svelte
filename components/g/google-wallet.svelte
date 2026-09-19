<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gz7b-8bsv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="gz7b-8bsv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-brands:google-wallet" {...props}></Icon>
