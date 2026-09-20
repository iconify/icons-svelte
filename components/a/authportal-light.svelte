<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bp-luevbc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="bp-luevbc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:authportal-light" {...props}></Icon>
