<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iqe986v7z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="iqe986v7z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:cloud-download" {...props}></Icon>
