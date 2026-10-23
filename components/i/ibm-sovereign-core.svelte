<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nwzr2q6id.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="nwzr2q6id"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:ibm-sovereign-core" {...props}></Icon>
