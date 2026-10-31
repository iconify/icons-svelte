<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/el40pyb8v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="el40pyb8v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:hexagon-plus-round" {...props}></Icon>
