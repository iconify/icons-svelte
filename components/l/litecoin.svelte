<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qutl96rfe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qutl96rfe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:litecoin" {...props}></Icon>
