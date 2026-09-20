<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pnl4as1cj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pnl4as1cj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:paradox-interactive" {...props}></Icon>
