<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wyd8d0txh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wyd8d0txh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:pool-disolved" {...props}></Icon>
