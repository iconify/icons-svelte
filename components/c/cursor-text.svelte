<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jh76xkagn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jh76xkagn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:cursor-text" {...props}></Icon>
