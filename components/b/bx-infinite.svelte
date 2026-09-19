<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t1sdeeb9z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t1sdeeb9z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bx-infinite" {...props}></Icon>
