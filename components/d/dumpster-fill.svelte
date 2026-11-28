<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/emr687pzp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="emr687pzp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pullo:dumpster-fill" {...props}></Icon>
