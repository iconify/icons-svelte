<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yo-u1wbfe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yo-u1wbfe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:cursor-sparkle-fill-round" {...props}></Icon>
