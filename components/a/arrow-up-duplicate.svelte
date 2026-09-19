<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m-ue__bvy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="m-ue__bvy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dashicons:arrow-up-duplicate" {...props}></Icon>
