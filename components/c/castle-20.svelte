<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/suy8wqlre.css';
import '../../css/r/rxepc7-8f.css';
import '../../css/n/ni152fyap.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="suy8wqlre"/><path class="rxepc7-8f"/><path class="ni152fyap"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:castle-20" {...props}></Icon>
