<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ecf22k6ia.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ecf22k6ia"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:betula" {...props}></Icon>
