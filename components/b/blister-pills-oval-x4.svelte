<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ig5g98dmx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="ig5g98dmx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:blister-pills-oval-x4" {...props}></Icon>
