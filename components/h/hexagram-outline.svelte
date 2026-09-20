<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a393mfb-f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a393mfb-f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:hexagram-outline" {...props}></Icon>
