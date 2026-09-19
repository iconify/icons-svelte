<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m19nw0dzp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="m19nw0dzp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:jet-fighter" {...props}></Icon>
