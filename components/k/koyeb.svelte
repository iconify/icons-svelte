<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ikr5asbjo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ikr5asbjo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:koyeb" {...props}></Icon>
