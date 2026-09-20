<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b-ez5do3d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="b-ez5do3d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:html" {...props}></Icon>
