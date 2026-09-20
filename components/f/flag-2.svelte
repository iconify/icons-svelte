<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oa_qoyf3k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":25,"height":25};
const content = `<path class="oa_qoyf3k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:flag-2" {...props}></Icon>
