<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j7kwcebrx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j7kwcebrx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:apple-arcade" {...props}></Icon>
