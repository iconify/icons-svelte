<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d1na8bbbx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d1na8bbbx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:archive2-filled" {...props}></Icon>
