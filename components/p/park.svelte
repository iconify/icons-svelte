<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q64u7cctz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q64u7cctz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-cyber:park" {...props}></Icon>
