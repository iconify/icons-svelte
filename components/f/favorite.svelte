<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lrmpikusq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lrmpikusq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mi:favorite" {...props}></Icon>
