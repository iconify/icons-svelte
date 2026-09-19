<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bo5a97nhk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="bo5a97nhk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:face-sad-stroke-16" {...props}></Icon>
