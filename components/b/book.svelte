<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n6q9m7bmx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n6q9m7bmx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:book" {...props}></Icon>
