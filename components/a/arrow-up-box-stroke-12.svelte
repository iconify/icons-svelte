<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fns4x3b6b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="fns4x3b6b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:arrow-up-box-stroke-12" {...props}></Icon>
