<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kc5ykcb0u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="kc5ykcb0u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:microsoft-yammer-logo-2-solid" {...props}></Icon>
