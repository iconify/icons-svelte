<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vjph59xfl.css';
import '../../css/p/pg557kbil.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vjph59xfl"/><path class="pg557kbil"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:face-thinking-solid" {...props}></Icon>
