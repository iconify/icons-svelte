<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/en1w-_b0x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="en1w-_b0x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:pill-off" {...props}></Icon>
