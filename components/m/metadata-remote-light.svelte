<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g7w7ozbih.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="g7w7ozbih"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:metadata-remote-light" {...props}></Icon>
