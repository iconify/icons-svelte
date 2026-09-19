<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e4erq1bzb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="e4erq1bzb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:male-female-sharp" {...props}></Icon>
