<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cfh0tyb9x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cfh0tyb9x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:recycle-line" {...props}></Icon>
