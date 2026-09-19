<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kophwxlgh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":458,"height":512};
const content = `<path class="kophwxlgh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:restql" {...props}></Icon>
