<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lrz1_6xna.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lrz1_6xna"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:badge-indian-rupee-fill" {...props}></Icon>
