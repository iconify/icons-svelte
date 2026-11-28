<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mj7443xlf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mj7443xlf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:plug-check" {...props}></Icon>
