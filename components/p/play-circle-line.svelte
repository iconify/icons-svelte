<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w3z640blx.css';
import '../../css/k/k4dbl06su.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w3z640blx"/><path class="k4dbl06su"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:play-circle-line" {...props}></Icon>
