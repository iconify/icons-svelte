<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r9xj9c1ac.css';
import '../../css/e/ec97ebbsu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="r9xj9c1ac"/><path class="ec97ebbsu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:notion-mail" {...props}></Icon>
