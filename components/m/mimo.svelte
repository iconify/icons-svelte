<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cl4o9rb6a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cl4o9rb6a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:mimo" {...props}></Icon>
