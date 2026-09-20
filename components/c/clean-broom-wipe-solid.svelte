<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w3v7l-00h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="w3v7l-00h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:clean-broom-wipe-solid" {...props}></Icon>
