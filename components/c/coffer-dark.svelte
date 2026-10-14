<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dwl3inblv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="dwl3inblv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:coffer-dark" {...props}></Icon>
