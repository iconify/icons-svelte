<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e1i32sk4o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e1i32sk4o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:aquarius" {...props}></Icon>
