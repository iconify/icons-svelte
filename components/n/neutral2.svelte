<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xc8c-nbos.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="xc8c-nbos"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:neutral2" {...props}></Icon>
