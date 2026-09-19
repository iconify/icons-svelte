<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nuwikiitw.css';
import '../../css/f/f7t-e2bsi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="nuwikiitw"/><path class="f7t-e2bsi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:flow-stream" {...props}></Icon>
