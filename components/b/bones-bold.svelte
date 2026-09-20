<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fo3ldvyho.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fo3ldvyho"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:bones-bold" {...props}></Icon>
