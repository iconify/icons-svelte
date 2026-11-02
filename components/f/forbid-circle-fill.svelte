<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u28i3mbca.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u28i3mbca"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:forbid-circle-fill" {...props}></Icon>
