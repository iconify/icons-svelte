<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u1ro-p46f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u1ro-p46f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:focus-fill" {...props}></Icon>
