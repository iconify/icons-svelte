<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n-s921btx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="n-s921btx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:language" {...props}></Icon>
