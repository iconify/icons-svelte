<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i4d9iffrr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="i4d9iffrr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:adobe-audio-logo-solid" {...props}></Icon>
