<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jq3ztmbcu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="jq3ztmbcu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:aurelia" {...props}></Icon>
