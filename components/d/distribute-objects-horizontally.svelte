<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/crxncckvz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="crxncckvz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:distribute-objects-horizontally" {...props}></Icon>
