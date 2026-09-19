<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bp4eogk8d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bp4eogk8d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:3dprinter-printing" {...props}></Icon>
