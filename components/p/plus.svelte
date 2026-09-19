<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a6tvq3b9g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="a6tvq3b9g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="entypo:plus" {...props}></Icon>
