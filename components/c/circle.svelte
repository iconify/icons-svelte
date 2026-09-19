<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/plwc9ubfc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="plwc9ubfc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icons8:circle" {...props}></Icon>
