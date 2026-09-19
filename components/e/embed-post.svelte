<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mg3a_acxa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="mg3a_acxa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dashicons:embed-post" {...props}></Icon>
