<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s8rv-gtdd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s8rv-gtdd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-cyber:cloud" {...props}></Icon>
