<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s8l5l3cxn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":896,"height":1024};
const content = `<path class="s8l5l3cxn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:lock" {...props}></Icon>
