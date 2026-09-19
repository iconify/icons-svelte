<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m8l0bzpzn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":896,"height":1024};
const content = `<path class="m8l0bzpzn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:batteryaltfull" {...props}></Icon>
