<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m7sl2bb-w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":576,"height":512};
const content = `<path class="m7sl2bb-w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:child-rifle" {...props}></Icon>
