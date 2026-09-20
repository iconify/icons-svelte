<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gd8-kbjvy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="gd8-kbjvy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:p" {...props}></Icon>
