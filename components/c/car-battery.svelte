<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kcyrh0b4i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="kcyrh0b4i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:car-battery" {...props}></Icon>
