<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/io0rh2bye.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="io0rh2bye"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:cut" {...props}></Icon>
