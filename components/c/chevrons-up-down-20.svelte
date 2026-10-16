<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ot99fcl4y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ot99fcl4y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:chevrons-up-down-20" {...props}></Icon>
