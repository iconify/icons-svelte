<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h7b17ac9h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h7b17ac9h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:location-filled" {...props}></Icon>
