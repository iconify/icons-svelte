<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nc05hybdw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="nc05hybdw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pullo:ethernet-thin" {...props}></Icon>
