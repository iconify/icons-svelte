<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i0n_0r0ph.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i0n_0r0ph"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:book" {...props}></Icon>
