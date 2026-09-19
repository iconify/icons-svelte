<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pm0-dsbho.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="pm0-dsbho"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:fantom" {...props}></Icon>
