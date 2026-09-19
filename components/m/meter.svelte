<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/feqmr1ozi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="feqmr1ozi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:meter" {...props}></Icon>
