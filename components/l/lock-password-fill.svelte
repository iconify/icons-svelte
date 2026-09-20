<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pyaqjjqzn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pyaqjjqzn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:lock-password-fill" {...props}></Icon>
