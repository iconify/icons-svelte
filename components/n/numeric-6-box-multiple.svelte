<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vuhumb8sa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vuhumb8sa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:numeric-6-box-multiple" {...props}></Icon>
