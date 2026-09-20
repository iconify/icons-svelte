<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tw9vr5bmz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="tw9vr5bmz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:flathub-light" {...props}></Icon>
