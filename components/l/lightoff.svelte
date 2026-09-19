<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g0cdhsbug.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1025,"height":1025};
const content = `<path class="g0cdhsbug"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:lightoff" {...props}></Icon>
