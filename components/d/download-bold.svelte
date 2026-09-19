<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wuilmgbcd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wuilmgbcd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:download-bold" {...props}></Icon>
