<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/di684mbed.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1200,"height":1200};
const content = `<path class="di684mbed"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="el:plus" {...props}></Icon>
