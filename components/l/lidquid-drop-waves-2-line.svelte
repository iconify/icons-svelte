<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hux62626x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hux62626x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="majesticons:lidquid-drop-waves-2-line" {...props}></Icon>
