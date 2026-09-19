<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fgdtsgbcc.css';
import '../../css/v/vj4rr6bnv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="fgdtsgbcc"/><path class="vj4rr6bnv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:delete" {...props}></Icon>
