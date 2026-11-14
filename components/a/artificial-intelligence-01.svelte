<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/je3s1s1ux.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="je3s1s1ux"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:artificial-intelligence-01" {...props}></Icon>
