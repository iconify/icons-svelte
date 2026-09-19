<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ac5rqkw9o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ac5rqkw9o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:egg-sharp" {...props}></Icon>
