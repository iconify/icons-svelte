<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wvq5dx-8z.css';
import '../../css/n/nj-jrfb9w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wvq5dx-8z"/><path class="nj-jrfb9w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:handshake-solid" {...props}></Icon>
