<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i0d--hudv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="i0d--hudv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="temaki:pier-fixed" {...props}></Icon>
