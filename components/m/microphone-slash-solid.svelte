<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z30xycbrp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z30xycbrp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:microphone-slash-solid" {...props}></Icon>
