<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q82bwqbxy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q82bwqbxy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:mail-x" {...props}></Icon>
