<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rxnsrcbjt.css';
import '../../css/u/uw344sgbq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rxnsrcbjt"/><path class="uw344sgbq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:arrow-button-right-1-bold" {...props}></Icon>
