<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b430c0b3m.css';
import '../../css/t/tvql3c4ij.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b430c0b3m"/><path class="tvql3c4ij"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:moderate-snow-fill" {...props}></Icon>
