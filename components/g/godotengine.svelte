<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s80gwi9yn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s80gwi9yn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:godotengine" {...props}></Icon>
