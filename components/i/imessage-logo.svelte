<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yse773b8l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yse773b8l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:imessage-logo" {...props}></Icon>
