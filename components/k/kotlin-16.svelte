<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t2_6hebam.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="t2_6hebam"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nonicons:kotlin-16" {...props}></Icon>
