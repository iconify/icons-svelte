<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d1fnr5b7d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d1fnr5b7d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:football-filled" {...props}></Icon>
