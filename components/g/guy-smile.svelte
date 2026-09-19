<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m4yi8cb7t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="m4yi8cb7t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:guy-smile" {...props}></Icon>
