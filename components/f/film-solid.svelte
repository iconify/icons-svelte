<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yh0t3pb5g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yh0t3pb5g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:film-solid" {...props}></Icon>
