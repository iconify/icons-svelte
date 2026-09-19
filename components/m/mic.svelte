<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dsxk0_bpo.css';
import '../../css/u/usq2d7duw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":17,"height":24};
const content = `<path class="dsxk0_bpo"/><path class="usq2d7duw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:mic" {...props}></Icon>
