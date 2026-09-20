<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qrv9ke-ph.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qrv9ke-ph"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:presentation-solid" {...props}></Icon>
