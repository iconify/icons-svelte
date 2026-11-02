<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hw38jrbcn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hw38jrbcn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:map-minus-fill" {...props}></Icon>
