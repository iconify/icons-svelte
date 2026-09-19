<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xb1dfs46w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xb1dfs46w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:kaufland" {...props}></Icon>
