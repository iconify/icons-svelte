<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/epyppjbhw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="epyppjbhw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:cross" {...props}></Icon>
