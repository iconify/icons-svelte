<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/svhbf3bmr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="svhbf3bmr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:fullscreen-exit-fill" {...props}></Icon>
