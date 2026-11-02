<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xzf2re38v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xzf2re38v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:bed-single-line" {...props}></Icon>
