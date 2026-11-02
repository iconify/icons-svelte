<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nk-f31lyk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nk-f31lyk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:rare-fog-lights-fill" {...props}></Icon>
