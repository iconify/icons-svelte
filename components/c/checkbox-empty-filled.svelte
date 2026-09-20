<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/voasgl06y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="voasgl06y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:checkbox-empty-filled" {...props}></Icon>
