<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vmvu6ublf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vmvu6ublf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:incognito-mode-solid" {...props}></Icon>
