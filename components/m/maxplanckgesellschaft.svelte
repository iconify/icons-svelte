<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i4xp6obcc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i4xp6obcc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:maxplanckgesellschaft" {...props}></Icon>
