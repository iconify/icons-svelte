<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sddwh4xus.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1020,"height":1024};
const content = `<path class="sddwh4xus"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:mute" {...props}></Icon>
