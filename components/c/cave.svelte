<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m2nepdh6e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="m2nepdh6e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:cave" {...props}></Icon>
