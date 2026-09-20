<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v-vtlgbgt.css';
import '../../css/g/gh2oltbob.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="v-vtlgbgt"/><path class="gh2oltbob"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:iobroker" {...props}></Icon>
