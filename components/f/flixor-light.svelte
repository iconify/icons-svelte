<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b6wgsrbtn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="b6wgsrbtn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:flixor-light" {...props}></Icon>
