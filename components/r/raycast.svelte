<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/seu7efbmi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="seu7efbmi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:raycast" {...props}></Icon>
