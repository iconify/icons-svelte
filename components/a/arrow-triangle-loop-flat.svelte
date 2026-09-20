<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s8o24499m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="s8o24499m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp-color:arrow-triangle-loop-flat" {...props}></Icon>
