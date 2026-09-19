<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e0a3f7ftz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":512};
const content = `<path class="e0a3f7ftz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:person-hiking" {...props}></Icon>
