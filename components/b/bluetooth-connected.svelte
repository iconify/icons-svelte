<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hdvspgbei.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hdvspgbei"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:bluetooth-connected" {...props}></Icon>
