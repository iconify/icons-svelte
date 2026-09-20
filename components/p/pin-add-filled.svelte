<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s4rk8eb7z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="s4rk8eb7z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:pin-add-filled" {...props}></Icon>
