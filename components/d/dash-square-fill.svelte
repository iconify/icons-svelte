<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hugaiacrs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="hugaiacrs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:dash-square-fill" {...props}></Icon>
