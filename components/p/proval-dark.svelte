<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w6knyybng.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="w6knyybng"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:proval-dark" {...props}></Icon>
