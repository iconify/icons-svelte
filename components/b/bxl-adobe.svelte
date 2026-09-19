<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b6o6jm30f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b6o6jm30f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxl-adobe" {...props}></Icon>
