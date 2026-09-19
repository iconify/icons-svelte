<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c83t9k23a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c83t9k23a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-left-arrow-circle" {...props}></Icon>
