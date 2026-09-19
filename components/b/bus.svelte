<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/be96qhxef.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="be96qhxef"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:bus" {...props}></Icon>
