<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f8r6-nb4a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="f8r6-nb4a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:location-heart-pin-solid" {...props}></Icon>
