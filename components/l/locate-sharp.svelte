<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l3c6jabxb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="l3c6jabxb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:locate-sharp" {...props}></Icon>
