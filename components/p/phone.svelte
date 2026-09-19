<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i3r6n63fd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i3r6n63fd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="guidance:phone" {...props}></Icon>
