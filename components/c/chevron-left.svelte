<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qs93c7boo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="qs93c7boo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nimbus:chevron-left" {...props}></Icon>
