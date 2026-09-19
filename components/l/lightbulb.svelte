<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/guzb39b0z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="guzb39b0z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:lightbulb" {...props}></Icon>
