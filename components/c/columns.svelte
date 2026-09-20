<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iyd2yshmg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iyd2yshmg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uit:columns" {...props}></Icon>
