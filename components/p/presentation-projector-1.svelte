<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c85-vrb9e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c85-vrb9e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:presentation-projector-1" {...props}></Icon>
