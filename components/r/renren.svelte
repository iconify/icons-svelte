<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t2hbt2bqi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="t2hbt2bqi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:renren" {...props}></Icon>
