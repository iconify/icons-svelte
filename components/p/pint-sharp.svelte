<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vdsiym1km.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="vdsiym1km"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:pint-sharp" {...props}></Icon>
