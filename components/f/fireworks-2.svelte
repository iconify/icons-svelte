<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n_idn1bng.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="n_idn1bng"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand:fireworks-2" {...props}></Icon>
