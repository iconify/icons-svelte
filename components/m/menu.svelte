<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zssm2xbet.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="zssm2xbet"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="rivet-icons:menu" {...props}></Icon>
