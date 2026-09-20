<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xmjdt9dtj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xmjdt9dtj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:bug" {...props}></Icon>
