<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/psstizbti.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="psstizbti"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:analogue" {...props}></Icon>
