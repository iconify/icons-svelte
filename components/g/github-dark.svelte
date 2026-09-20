<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hajm5gbsc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="hajm5gbsc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:github-dark" {...props}></Icon>
