<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/azc0-rwwk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1792,"height":1792};
const content = `<path class="azc0-rwwk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vs:f054" {...props}></Icon>
