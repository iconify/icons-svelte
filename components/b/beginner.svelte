<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q09i7jb2a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q09i7jb2a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fe:beginner" {...props}></Icon>
