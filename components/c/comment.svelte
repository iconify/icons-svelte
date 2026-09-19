<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yo1lg9b4t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="yo1lg9b4t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:comment" {...props}></Icon>
