<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e_v4g-bby.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="e_v4g-bby"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:land-mine-on" {...props}></Icon>
