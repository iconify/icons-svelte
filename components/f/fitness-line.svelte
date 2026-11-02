<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/msj8-dbor.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="msj8-dbor"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:fitness-line" {...props}></Icon>
