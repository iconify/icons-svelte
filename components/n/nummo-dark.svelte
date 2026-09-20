<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z172f6bjb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="z172f6bjb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:nummo-dark" {...props}></Icon>
