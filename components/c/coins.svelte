<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fbyx1dbzp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="fbyx1dbzp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:coins" {...props}></Icon>
