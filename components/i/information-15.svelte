<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ltx671b8d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="ltx671b8d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:information-15" {...props}></Icon>
