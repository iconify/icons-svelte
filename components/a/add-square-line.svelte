<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h7kuph5gx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h7kuph5gx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:add-square-line" {...props}></Icon>
