<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qw1oqzbhg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qw1oqzbhg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:chemical-hexagon-1-bold" {...props}></Icon>
