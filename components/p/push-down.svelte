<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y9sk6wbsc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":21,"height":21};
const content = `<path class="y9sk6wbsc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="system-uicons:push-down" {...props}></Icon>
