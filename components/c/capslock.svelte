<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mf5cy-bbx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":896,"height":1024};
const content = `<path class="mf5cy-bbx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:capslock" {...props}></Icon>
