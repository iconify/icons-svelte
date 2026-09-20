<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cizwry8ue.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="cizwry8ue"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:circle-a" {...props}></Icon>
