<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ym_0hibad.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ym_0hibad"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:book-shelf-fill" {...props}></Icon>
