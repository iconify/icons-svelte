<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tob8s0bkk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="tob8s0bkk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:gardener" {...props}></Icon>
