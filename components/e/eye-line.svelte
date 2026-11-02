<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bp4j6nmbf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bp4j6nmbf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:eye-line" {...props}></Icon>
