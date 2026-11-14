<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kg8z4pjgc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="kg8z4pjgc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:papermark-dark" {...props}></Icon>
