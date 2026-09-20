<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f_9led-1s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="f_9led-1s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:medium-logo-2-solid" {...props}></Icon>
