<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c5z12szzz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c5z12szzz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:bookmark" {...props}></Icon>
