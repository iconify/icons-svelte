<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/my0clspsq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="my0clspsq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:browser-build-solid" {...props}></Icon>
