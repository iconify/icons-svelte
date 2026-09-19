<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kdf0cbbal.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="kdf0cbbal"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fad:arpdownandup" {...props}></Icon>
