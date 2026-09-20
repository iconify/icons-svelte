<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u2_5ntbeb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u2_5ntbeb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:forward-10-fill" {...props}></Icon>
