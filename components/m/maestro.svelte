<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m0iym6bem.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":26,"height":26};
const content = `<path class="m0iym6bem"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wpf:maestro" {...props}></Icon>
