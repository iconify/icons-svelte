<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m2t2l_3rn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="m2t2l_3rn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:appveyor" {...props}></Icon>
