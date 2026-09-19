<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/de3s681aw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="de3s681aw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:orthogon9x9" {...props}></Icon>
