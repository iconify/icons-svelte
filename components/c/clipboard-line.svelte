<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mg9elfixr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mg9elfixr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:clipboard-line" {...props}></Icon>
