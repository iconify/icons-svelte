<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ctoz3fbuh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ctoz3fbuh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:hanko-dark" {...props}></Icon>
