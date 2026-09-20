<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ny7qrabjb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":50,"height":50};
const content = `<path class="ny7qrabjb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="marketeq:microphone" {...props}></Icon>
