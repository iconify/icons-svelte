<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bo14_sr-k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="bo14_sr-k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:menu-fill-16" {...props}></Icon>
