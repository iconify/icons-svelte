<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m9b3_-bgn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="m9b3_-bgn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:earbuds-20" {...props}></Icon>
