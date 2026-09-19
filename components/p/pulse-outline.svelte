<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r2jvoxbqh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="r2jvoxbqh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:pulse-outline" {...props}></Icon>
