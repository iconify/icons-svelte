<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c1z4cb9qa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="c1z4cb9qa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:basketball" {...props}></Icon>
