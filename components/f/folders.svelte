<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f2nnsl4rl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f2nnsl4rl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:folders" {...props}></Icon>
