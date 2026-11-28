<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jf0f0uh5k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jf0f0uh5k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:backpack" {...props}></Icon>
