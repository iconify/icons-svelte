<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fokbu2brg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="fokbu2brg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:level-up-alt" {...props}></Icon>
