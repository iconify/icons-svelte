<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/skx7hxbky.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="skx7hxbky"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:minimize" {...props}></Icon>
