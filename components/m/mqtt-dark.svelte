<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/di3lwkbiw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="di3lwkbiw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:mqtt-dark" {...props}></Icon>
