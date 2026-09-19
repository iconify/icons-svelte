<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eh_ti6dfs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eh_ti6dfs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:play-solid" {...props}></Icon>
