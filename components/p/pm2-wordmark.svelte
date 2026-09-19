<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c8cdc8b8v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="c8cdc8b8v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:pm2-wordmark" {...props}></Icon>
