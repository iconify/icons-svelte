<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pwplii8cf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":450,"height":512};
const content = `<path class="pwplii8cf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:ensime" {...props}></Icon>
