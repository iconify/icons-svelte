<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z8oew7wwi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z8oew7wwi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:aqara-a100" {...props}></Icon>
