<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nx1nbrbzs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nx1nbrbzs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:claude-fill" {...props}></Icon>
