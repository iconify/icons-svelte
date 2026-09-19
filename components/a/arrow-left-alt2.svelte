<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v1r1b3bgi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="v1r1b3bgi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dashicons:arrow-left-alt2" {...props}></Icon>
