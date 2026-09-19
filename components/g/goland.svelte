<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qbjydlb0d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="qbjydlb0d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:goland" {...props}></Icon>
