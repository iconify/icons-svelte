<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fjw0-gioz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fjw0-gioz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:gesture-up-2" {...props}></Icon>
