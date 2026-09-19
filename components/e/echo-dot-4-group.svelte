<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e_2i16b-p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e_2i16b-p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:echo-dot-4-group" {...props}></Icon>
