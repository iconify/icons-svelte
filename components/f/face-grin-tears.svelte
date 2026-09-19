<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fe5k7yzpc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="fe5k7yzpc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-regular:face-grin-tears" {...props}></Icon>
