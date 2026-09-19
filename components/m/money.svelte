<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aaw36fbcd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":750,"height":710};
const content = `<path class="aaw36fbcd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="il:money" {...props}></Icon>
