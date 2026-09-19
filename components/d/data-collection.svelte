<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e39ud6bwf.css';
import '../../css/x/xbfcx7b2l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<circle class="e39ud6bwf"/><path class="xbfcx7b2l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:data-collection" {...props}></Icon>
