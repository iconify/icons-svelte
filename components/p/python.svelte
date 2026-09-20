<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jo9on0mrg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jo9on0mrg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:python" {...props}></Icon>
