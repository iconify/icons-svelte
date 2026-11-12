<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/si0pir4by.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="si0pir4by"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:composerize-light" {...props}></Icon>
