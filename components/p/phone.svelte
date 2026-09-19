<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jmsy4ybos.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jmsy4ybos"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:phone" {...props}></Icon>
