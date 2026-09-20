<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ys6txvbrd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ys6txvbrd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:key-return-16" {...props}></Icon>
