<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bmiyzeyex.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1664,"height":1536};
const content = `<path class="bmiyzeyex"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:archive" {...props}></Icon>
