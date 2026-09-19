<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h4-0o5epi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="h4-0o5epi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:arrow-down-circle-sharp" {...props}></Icon>
