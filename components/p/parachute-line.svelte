<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ydkyh5cpf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ydkyh5cpf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:parachute-line" {...props}></Icon>
