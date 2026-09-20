<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qrjc3wo0u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qrjc3wo0u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:dots-vertical-circle-outline" {...props}></Icon>
