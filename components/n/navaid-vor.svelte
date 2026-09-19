<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e39ud6bwf.css';
import '../../css/g/ga9tj3sth.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<circle class="e39ud6bwf"/><path class="ga9tj3sth"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:navaid-vor" {...props}></Icon>
