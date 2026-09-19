<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m4hofbbri.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="m4hofbbri"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:ibm-vsi-on-vpc-for-regulated-industries" {...props}></Icon>
