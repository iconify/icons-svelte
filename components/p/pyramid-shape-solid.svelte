<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uukcbebvz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="uukcbebvz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:pyramid-shape-solid" {...props}></Icon>
