<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ii7a4u0gn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ii7a4u0gn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:hyper" {...props}></Icon>
