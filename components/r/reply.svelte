<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jomkcf3yg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jomkcf3yg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:reply" {...props}></Icon>
