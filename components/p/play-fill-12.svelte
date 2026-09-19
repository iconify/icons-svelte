<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xfd3q5bgt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="xfd3q5bgt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:play-fill-12" {...props}></Icon>
