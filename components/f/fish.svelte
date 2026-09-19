<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wy5enpbrn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wy5enpbrn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:fish" {...props}></Icon>
