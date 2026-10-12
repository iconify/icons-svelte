<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t2m1qqb7g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="t2m1qqb7g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:flow-stroke-20" {...props}></Icon>
