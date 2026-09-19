<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gi5crlb6r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="gi5crlb6r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:gifts" {...props}></Icon>
