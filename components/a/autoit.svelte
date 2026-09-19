<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wdy0823vy.css';
import '../../css/e/edp5htv8r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="wdy0823vy"/><path class="edp5htv8r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:autoit" {...props}></Icon>
