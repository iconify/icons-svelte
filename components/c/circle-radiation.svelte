<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pbf5acc-u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="pbf5acc-u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:circle-radiation" {...props}></Icon>
