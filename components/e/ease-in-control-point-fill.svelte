<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fq7wvsbha.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fq7wvsbha"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:ease-in-control-point-fill" {...props}></Icon>
