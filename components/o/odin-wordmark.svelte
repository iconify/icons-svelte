<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ojvdfhb-d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="ojvdfhb-d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:odin-wordmark" {...props}></Icon>
