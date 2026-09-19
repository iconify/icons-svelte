<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gt-5-tn3f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="gt-5-tn3f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:nx" {...props}></Icon>
