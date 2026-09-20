<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mfvh-zmer.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mfvh-zmer"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:clock-fill" {...props}></Icon>
