<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xcyd7zbcd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xcyd7zbcd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:crosshair-alt" {...props}></Icon>
