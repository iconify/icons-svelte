<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wud-c2bls.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wud-c2bls"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:numbers-2-1" {...props}></Icon>
