<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gtchp6bvz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="gtchp6bvz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:navigate-circle-sharp" {...props}></Icon>
