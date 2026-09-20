<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mf4em36ny.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="mf4em36ny"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:cachet" {...props}></Icon>
