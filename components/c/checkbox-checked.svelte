<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hxv8z0l9j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="hxv8z0l9j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:checkbox-checked" {...props}></Icon>
