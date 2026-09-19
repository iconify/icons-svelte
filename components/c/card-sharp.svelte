<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wslkg7oxz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="wslkg7oxz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:card-sharp" {...props}></Icon>
