<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u5pw0tbde.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u5pw0tbde"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:linktap" {...props}></Icon>
