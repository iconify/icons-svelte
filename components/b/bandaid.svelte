<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l7gc5fn4t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="l7gc5fn4t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:bandaid" {...props}></Icon>
