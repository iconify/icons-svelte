<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l-95x3bia.css';
import '../../css/h/hdz9ffk6k.css';
import '../../css/m/m2o3sh-9c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":36,"height":36};
const content = `<path class="clr-i-outline clr-i-outline-path-1 l-95x3bia"/><path class="clr-i-outline clr-i-outline-path-2 hdz9ffk6k"/><path class="m2o3sh-9c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="clarity:resize-line" {...props}></Icon>
