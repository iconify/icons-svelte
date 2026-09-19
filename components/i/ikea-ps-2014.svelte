<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zqqot8bps.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zqqot8bps"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:ikea-ps-2014" {...props}></Icon>
