<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wiku2ln1k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wiku2ln1k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:figma-solid" {...props}></Icon>
