<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ni3s1zbnp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":512};
const content = `<path class="ni3s1zbnp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:mercury" {...props}></Icon>
