<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xvgy20fzr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xvgy20fzr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:hoopla" {...props}></Icon>
