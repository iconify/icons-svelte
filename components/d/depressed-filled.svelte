<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mwg1e6bof.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mwg1e6bof"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:depressed-filled" {...props}></Icon>
