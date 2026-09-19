<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uqgo409cl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="uqgo409cl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:inertiajs" {...props}></Icon>
