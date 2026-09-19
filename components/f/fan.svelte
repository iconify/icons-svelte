<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ks3zr9b-i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ks3zr9b-i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:fan" {...props}></Icon>
