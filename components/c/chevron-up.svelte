<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c7oca8soj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c7oca8soj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:chevron-up" {...props}></Icon>
