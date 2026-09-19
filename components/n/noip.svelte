<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zu-6n5ags.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zu-6n5ags"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:noip" {...props}></Icon>
