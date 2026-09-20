<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c5n-ojpms.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c5n-ojpms"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:arrow-up-left-from-circle" {...props}></Icon>
