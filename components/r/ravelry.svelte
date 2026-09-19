<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d_30-2b7p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="d_30-2b7p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-brands:ravelry" {...props}></Icon>
