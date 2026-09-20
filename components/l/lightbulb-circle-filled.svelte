<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hkcm51b9o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hkcm51b9o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:lightbulb-circle-filled" {...props}></Icon>
