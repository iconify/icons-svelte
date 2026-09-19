<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ejfwa9bbe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ejfwa9bbe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dashicons:arrow-down-alt2" {...props}></Icon>
