<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p4029nbaw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="p4029nbaw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:dollar" {...props}></Icon>
