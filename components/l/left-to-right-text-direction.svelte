<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cgwvj6b2r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cgwvj6b2r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:left-to-right-text-direction" {...props}></Icon>
