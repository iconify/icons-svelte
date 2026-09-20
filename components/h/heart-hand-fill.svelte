<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rixoy32sx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rixoy32sx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:heart-hand-fill" {...props}></Icon>
