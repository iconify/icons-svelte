<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lcg0lcc6u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":40,"height":40};
const content = `<path class="lcg0lcc6u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iwwa:close-braket" {...props}></Icon>
