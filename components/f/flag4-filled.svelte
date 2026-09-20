<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vnyi6su0z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vnyi6su0z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:flag4-filled" {...props}></Icon>
