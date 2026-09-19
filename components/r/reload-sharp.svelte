<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l-22auf4m.css';
import '../../css/h/h2afzob3l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="l-22auf4m"/><path class="h2afzob3l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:reload-sharp" {...props}></Icon>
