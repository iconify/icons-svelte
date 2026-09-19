<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h26p794_s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":487,"height":512};
const content = `<path class="h26p794_s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:husky" {...props}></Icon>
