<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eu1nxz26a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="eu1nxz26a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:meteor" {...props}></Icon>
