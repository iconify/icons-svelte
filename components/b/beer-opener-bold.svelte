<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xx63h-s5x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xx63h-s5x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:beer-opener-bold" {...props}></Icon>
