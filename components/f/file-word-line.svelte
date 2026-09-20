<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zt7vg02ge.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zt7vg02ge"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:file-word-line" {...props}></Icon>
