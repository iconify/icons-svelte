<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f3l1hd7pz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f3l1hd7pz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:bowl-fill" {...props}></Icon>
