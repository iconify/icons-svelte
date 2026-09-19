<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f-f8v1txm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="f-f8v1txm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:pixelshovel" {...props}></Icon>
