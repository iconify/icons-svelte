<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jz6z4yblv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jz6z4yblv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:golf" {...props}></Icon>
