<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tyiq1bcaa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tyiq1bcaa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:pencil" {...props}></Icon>
