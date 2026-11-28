<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ckgwp449k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ckgwp449k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:message-square-dashed-solid" {...props}></Icon>
