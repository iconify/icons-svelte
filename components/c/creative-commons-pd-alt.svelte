<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nt-g2-3ta.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="nt-g2-3ta"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-brands:creative-commons-pd-alt" {...props}></Icon>
