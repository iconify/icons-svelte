<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uoaqcj3qz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uoaqcj3qz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:cloud-fill" {...props}></Icon>
