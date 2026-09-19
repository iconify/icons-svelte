<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iyiz0gqma.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="iyiz0gqma"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:push-sharp" {...props}></Icon>
