<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/neqtoyb0j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="neqtoyb0j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:lion" {...props}></Icon>
