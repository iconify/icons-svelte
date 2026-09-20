<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ox_hucdtk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ox_hucdtk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:moai-line" {...props}></Icon>
