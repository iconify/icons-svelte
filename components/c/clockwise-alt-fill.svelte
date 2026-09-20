<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/edr4xvbmk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="edr4xvbmk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:clockwise-alt-fill" {...props}></Icon>
