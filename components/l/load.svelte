<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vkmrm2bze.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vkmrm2bze"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:load" {...props}></Icon>
