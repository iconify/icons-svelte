<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rlc4d9v9p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rlc4d9v9p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:adobe-lightroom-logo-solid" {...props}></Icon>
