<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/it-zmj3wk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="it-zmj3wk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:digg" {...props}></Icon>
