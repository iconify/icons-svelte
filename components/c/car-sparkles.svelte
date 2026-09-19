<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h5z6yebzw.css';
import '../../css/i/i9as8va8e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h5z6yebzw"/><path class="i9as8va8e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:car-sparkles" {...props}></Icon>
