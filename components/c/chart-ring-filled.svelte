<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/murc87bcv.css';
import '../../css/x/x0gfa0b7z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="murc87bcv"/><path class="x0gfa0b7z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:chart-ring-filled" {...props}></Icon>
