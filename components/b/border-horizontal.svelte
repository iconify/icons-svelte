<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hud2g9gnm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hud2g9gnm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uit:border-horizontal" {...props}></Icon>
