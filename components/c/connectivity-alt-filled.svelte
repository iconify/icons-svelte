<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dr381ccoh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dr381ccoh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:connectivity-alt-filled" {...props}></Icon>
