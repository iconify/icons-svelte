<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rbkbl3b0r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="rbkbl3b0r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:gap" {...props}></Icon>
