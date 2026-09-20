<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qwpwnrxha.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qwpwnrxha"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:battery-arrow-down" {...props}></Icon>
