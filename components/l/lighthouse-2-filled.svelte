<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tf4f4fryy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tf4f4fryy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:lighthouse-2-filled" {...props}></Icon>
