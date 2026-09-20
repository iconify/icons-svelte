<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hoh5_ms0c.css';
import '../../css/h/h-jbhd6rq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hoh5_ms0c"/><path class="h-jbhd6rq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:reflect-left-bold" {...props}></Icon>
