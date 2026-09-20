<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ajpmlpmwv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ajpmlpmwv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:openemr-light" {...props}></Icon>
