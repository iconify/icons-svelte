<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w33y4mbzr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w33y4mbzr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:center-focus-strong-filled" {...props}></Icon>
