<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z0tgn1auk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z0tgn1auk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:phone-cancel" {...props}></Icon>
