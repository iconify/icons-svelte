<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/otor3t_ow.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="otor3t_ow"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:bubble-fill" {...props}></Icon>
