<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sjjhel9ot.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="sjjhel9ot"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:meshping" {...props}></Icon>
