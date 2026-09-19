<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rc2w2q85y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="rc2w2q85y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:leaf" {...props}></Icon>
