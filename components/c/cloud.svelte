<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r8e9snbpz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r8e9snbpz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:cloud" {...props}></Icon>
